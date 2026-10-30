# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e7917c4ff6c660aba47b2df0c84f123d5bb1c3ce',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '29b4acf5af5214aef946828030a6e4e081f48d6d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'fef168c54ed2e37c314eb251806aaf9877f38465',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ee5c848a2612e27771ed14ec0c1674e1f798f21c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '9fbc2a782ee3f8a4db64e7d991e23da75e893f44',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'aa6dee8385afe4b2cc0152d086af2184743e16fd',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'bfac990e5eaed6acc4ba217e25d305cabd408740',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '271510bc50a1ecc65e62ca07dbf6b8dfe530dfd0',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'af7950f167455c91eb3c27754907e36f43c9cb2f',
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
