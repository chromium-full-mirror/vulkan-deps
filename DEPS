# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8a85691a0740d390761a1008b4696f57facd02c4',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '62c75b947fa8cb7830266cd9499daa3bc360896b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04b76709bf40a7ce8df3382060ef3620f19de566',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f657d2c15513d99473b9121100c8206939a399b2',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '16cedde3564629c43808401ad1eb3ca6ef24709a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8beef6cb63ffadb02300bf6321b4d3af85ea7417',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f0f308ad2cdc2e8fd58985d6230df4a29cc44eb6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'f216bb107bfc6d99a9605572963613e828b10880',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '075aaf59b5312fa96fd3d6de3f95499914fa2ec4',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
