# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2e24222cd9d19e737f8c790a2f485d5ba0d62166',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '9d0dbe9d59159ac936cdc56f9fc85e001afed183',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c8ad050fcb29e42a2f57d9f59e97488f465c436d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '54fc95232ced45f39348c091f6f95545588e350a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2cd90f9d20df57eac214c148f3aed885372ddcfe',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'da8d2caad9341ca8c5a7c3deba217d7da50a7c24',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '06ae73a3dc3a03466817d8370355203dac7b79b1',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'cb20eb451cf2e272daaf40099e864a916d8b5542',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5bac2eefc34e153e4af1665d5437958fa0cf9d15',
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
