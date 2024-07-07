# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4a516f28a17d3128f144affd7952142a90ab22e7',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '00c49e3b56cc9748228d2e5b0d1e8e9c4409a02f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '41a8eb27f1a7554dadfcdd45819954eaa94935e6',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9f2ccaef5f70c32bcd6c911a2b09dbb26106b437',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '4b9ea26d48f23e260c57bece311660d9e5c7ff23',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '38691803018cb2d85194b235faf43119d64c0a66',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7e13360e42364fdd1f07fe00f19d0432b12db055',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'df78ee39d2ff6c10b4f7f2ae06c7ca64524f9e25',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'adb959f5ab30f37c91e8f3b729b4b0a820cc855e',
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
